# Kubelet Service Kill

## Experiment Metadata

<table>
<tr>
<th> Name </th>
<th> Description </th>
<th> Documentation Link </th>
</tr>
<tr>
 <td> Kubelet Service Kill </td>
 <td> This experiment causes kubelet service kill gracefully for a certain chaos duration. The experiment aims to verify resiliency of applications whose replicas may be evicted or becomes unreachable on account on nodes turning unschedulable (Not Ready) due to kubelet service kill. </td>
 <td>  <a href=""> Added soon </a> </td>
 </tr>
 </table>

### Pipeline Runs


| Job ID |   Test Description         | Execution Time | Release Tag   | Test Result   |
 |---------|---------------------------| --------------|--------|--------|
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/180702">180702</a>           |  Kills the kubelet service on the application node.           | Wed Jul 22 02:11:20 2020(IST)  | ci | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/180079">180079</a>           |  Kills the kubelet service on the application node.           | Mon Jul 20 21:39:46 2020(IST)  | ci | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/179582">179582</a>           |  Kills the kubelet service on the application node.           | Mon Jul 20 13:33:40 2020(IST)  | ci | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/179096">179096</a>           |  Kills the kubelet service on the application node.           | Mon Jul 20 11:33:31 2020(IST)  | ci | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/178493">178493</a>           |  Kills the kubelet service on the application node.           | Fri Jul 17 07:18:50 2020(IST)  | latest | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/177527">177527</a>           |  Kills the kubelet service on the application node.           | Thu Jul 16 07:18:19 2020(IST)  | latest | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/177289">177289</a>           |  Kills the kubelet service on the application node.           | Wed Jul 15 19:54:33 2020(IST)  | latest | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/177139">177139</a>           |  Kills the kubelet service on the application node.           | Wed Jul 15 18:50:16 2020(IST)  | ci | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/177063">177063</a>           |  Kills the kubelet service on the application node.           | Wed Jul 15 17:22:41 2020(IST)  | latest | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/176466">176466</a>           |  Kills the kubelet service on the application node.           | Wed Jul 15 12:34:13 2020(IST)  | ci | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/176350">176350</a>           |  Kills the kubelet service on the application node.           | Wed Jul 15 11:41:08 2020(IST)  | ci | Failed :worried: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/175745">175745</a>           |  Kills the kubelet service on the application node.           | Wed Jul 15 03:24:32 2020(IST)  | ci | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/175714">175714</a>           |  Kills the kubelet service on the application node.           | Wed Jul 15 02:20:48 2020(IST)  | latest | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/175089">175089</a>           |  Kills the kubelet service on the application node.           | Tue Jul 14 21:09:45 2020(IST)  | latest | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/174988">174988</a>           |  Kills the kubelet service on the application node.           | Tue Jul 14 18:55:43 2020(IST)  | latest | Passed :smiley: |
|     <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/174814">174814</a>           |  Kills the kubelet service on the application node.           | Tue Jul 14 17:42:40 2020(IST)  | latest | Passed :smiley: |
 |    <a href= "https://gitlab.mayadata.io/litmuschaos/litmus-e2e/-/jobs/174733">174733</a>   |  Kills the kubelet service on the application node.           |  Tue Jul 14 15:19:11 2020(IST)     |latest  |Passed :smiley:  |
