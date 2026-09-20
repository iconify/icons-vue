<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="zyd8ut3ln"/><path class="wwjziacbw"/><path class="ssdd7-66y"/><path class="k9nyqcbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quickride" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k9nyqcbgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.918 22.339l-.883 2.746l-4.453-7.746l8.688-2.373l-1.304 2.655m5.12-5.923V17.7l2.406 2.464l3.156-1.866v-6.6h2.783l-5.49-5.622l-5.504 5.635zm2.739 1.729v4.587m-7.065 2.549c.767.383 1.533.766 2.125 1.316c.591.55 1.007 1.266 1.424 1.982");
}

.ssdd7-66y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.529 34.351c0-.79 0-1.581.051-2.316s.154-1.415.257-2.095m.421-1.69c.233-.635.466-1.269.989-1.996s1.336-1.548 2.15-2.37m1.381-1.431l3.131-2.428m-13.206 8.158c-.546-1.319-1.092-2.638-2.057-3.612s-2.346-1.603-3.729-2.233m2.051-4.717c1.263.49 2.526.979 3.643 1.787c1.118.808 2.091 1.935 3.064 3.062m11.357-.388l1.133 2.615l4.198-7.024l-8.268-2.647l.946 2.608M19.703 28.183l2.97-5.714");
}

.wwjziacbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.955 36.47c.017-3.652.034-7.304 1.715-10.444c1.68-3.139 5.025-5.765 8.37-8.392m-5.034 17.802c.13-2.347.262-4.695 1.433-6.92c1.17-2.225 3.382-4.33 5.593-6.433");
}

.zyd8ut3ln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.783 27.476c1.126-.874 2.253-1.747 3.208-1.455s1.741 1.752 2.356 2.04s1.058-.594 2.214-.437s3.025 1.354 3.716 2.495s.205 2.223.427 2.55c.222.328 1.152-.1 1.531.175s.21 1.254.619 1.49s1.4-.271 2.347-.039s1.851 1.204 2.756 2.175m5.05-1.034c1.14-.635 2.282-1.27 3.411-1.457s2.248.076 2.751-.173c.504-.25.393-1.01.81-1.184c.419-.175 1.366.236 1.699-.275c.333-.512.05-1.944.635-3.01s2.035-1.765 3.166-1.883s1.941.345 2.505.079c.563-.267.878-1.263 1.399-1.634c.52-.371 1.246-.118 1.971.135");
}

</style>
