## komora
<table style="width:100%">
<tr>
  <td>
    <table style="width:100%">
      <tr>
        <td><b>key</b></td>
        <td><b>value</b></td>
      </tr>
      <tr>
        <td>wtf?</td>
        <td>declassified components for constructing industrial stateful systems</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/marble">marble</a></td>
        <td>garbage-collecting object store for building your own kv or db on top of, built on top of tiny-lsm and pagetable</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/sharded-log">sharded-log</a></td>
        <td>atomic batch-aware low-contention logger that recovers logged items in-order, log updates here before periodically compacting them into Marble</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/tiny-lsm">tiny-lsm</a></td>
        <td>an extremely high performance kv store for constant-sized keys and values, supporting atomic write batches, ideal for managing system metadata</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/ebr">ebr</a></td>
        <td>extremely efficient epoch-based reclamation for deferring actions until after concurrent threads may be finished, built on top of shared-local-state</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/pagetable">pagetable</a></td>
        <td>wait-free 4-level pagetable that maps from u64 to &AtomicU64, ideal for managing concurrent metadata or shared state</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/art">art</a></td>
        <td>adaptive radix trie for somewhat-clumpy fixed-size keys</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/fault-injection">fault-injection</a></td>
        <td>if you have io::Error handling code, you should be using this crate to trigger it</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/shared-local-state">shared-local-state</a></td>
        <td>manage dynamic state that needs to be shared across concurrent threads</td>
      </tr>
      <tr>
        <td><a href="https://github.com/komora-io/pagecache">pagecache</a></td>
        <td>coming soon</td>
      </tr>
     </table>
  </td>
  <td>
    <p align="center">
      <img src="https://raw.githubusercontent.com/komora-io/.github/main/profile/Screenshot%202022-05-17%20at%2009-26-30%20Komora.png" width="50%" height="auto" />
    </p>
  </td>
 </tr>
</table>
