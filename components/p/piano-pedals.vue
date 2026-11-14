<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky9amabqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:piano-pedals" /></template>
<style>
.ky9amabqr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 2.25H6.75q-1.243 0-2.121.879q-.879.878-.879 2.121q0 3 3 3h10.5q3 0 3-3q0-1.243-.879-2.121q-.878-.879-2.121-.879m-10 7.5q.741 0 1.218.567t.349 1.297l-1.325 7.567q-.363 2.068-2.462 2.069H4.5q-1.119 0-1.756-.919q-.637-.92-.244-1.968l2.697-7.19Q5.731 9.75 7.249 9.75zm4.75 0q-1.679 0-1.846 1.67l-.708 7.081q-.111 1.104.634 1.927q.745.822 1.854.822h.132q1.109 0 1.854-.822q.745-.823.634-1.927l-.708-7.081Q13.679 9.75 12 9.75m4.75 0h.001q1.518 0 2.052 1.422l2.697 7.192q.393 1.047-.244 1.967q-.637.919-1.756.919h-.53q-2.099-.001-2.462-2.069l-1.325-7.567q-.128-.73.349-1.297t1.218-.567");
}

</style>
