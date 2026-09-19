<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xpk6d0b1o"/><path class="ckfh6ib5u"/><path class="zzmmt2b4j"/><rect class="igk4whiqo"/><path class="rqhxrid1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:podcastguru" /></template>
<style>
.ckfh6ib5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.766 32.293c1.175-.129 2.349-.406 3.494-.696c4.068-.824 7.509-3.776 9.24-7.512c-1.79-3.855-5.337-6.919-9.576-7.64c-1.033-.23-2.062-.449-3.115-.555a31 31 0 0 0-.362-2.608c-.59-4.319-3.672-7.975-7.577-9.782c-4.448 2.074-7.37 6.668-7.887 11.485c-.034.256-.077.563-.103.82c-.987.102-1.976.343-2.94.57c-4.165.769-7.679 3.746-9.44 7.562c1.829 3.957 5.61 7.072 9.998 7.593c.705.12 1.449.207 2.16.278c.108 1.04.313 2.07.524 3.095c.655 4.229 3.71 7.817 7.54 9.597c3.788-1.753 6.768-5.228 7.54-9.365c.218-.93.406-1.893.504-2.843Zm-7.939-.104v5.288");
}

.igk4whiqo {
  width: 8.449px;
  height: 17.967px;
  x: 19.671px;
  y: 11.018px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.224px;
  ry: 4.224px;
}

.rqhxrid1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.671 20.002h8.449");
}

.xpk6d0b1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.785 30.59c.674 2.599.33 5.363-.519 7.883c-2.52.848-5.313 1.163-7.913.49M17.48 9.066c-2.66-.63-5.5-.568-8.1.31c-.833 2.57-1.245 5.493-.403 8.11m21.249-8.463c2.658-.991 5.659-.53 8.297.322c.868 2.58 1.197 5.448.38 8.087M8.908 30.349c-.673 2.6-.33 5.363.519 7.883c2.52.848 5.313 1.163 7.913.49");
}

.zzmmt2b4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.179 21.98c-.01 2.474.276 5.204-1.447 7.242c-2.638 3.68-8.683 3.816-11.492.27c-1.946-2.1-1.658-4.897-1.663-7.512");
}

</style>
