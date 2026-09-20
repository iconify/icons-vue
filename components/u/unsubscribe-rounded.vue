<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmof-8b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unsubscribe-rounded" /></template>
<style>
.hmof-8b5d {
  fill: currentColor;
  d: path("M12 11L4.82 6.32q-.195-.122-.402-.045t-.264.289q-.058.148-.015.306q.042.159.184.246l7.229 4.713q.212.13.448.13t.448-.13l7.229-4.713q.142-.087.194-.246q.052-.158-.025-.306q-.057-.212-.264-.28q-.207-.067-.401.055zm4.165 9.836Q15 19.67 15 18t1.165-2.835T19 14t2.836 1.165T23 18t-1.164 2.836T19 22t-2.835-1.164m.874-2.451h3.922q.162 0 .274-.112q.111-.111.111-.273t-.111-.273t-.273-.111h-3.924q-.161 0-.273.111q-.111.112-.111.273t.111.273t.273.112M4.616 19q-.672 0-1.144-.472T3 17.385V6.615q0-.67.472-1.143Q3.944 5 4.616 5h14.769q.67 0 1.143.472q.472.472.472 1.144v4.776q0 .354-.279.566t-.646.138q-.258-.067-.534-.081Q19.264 12 19 12q-2.502 0-4.251 1.749T13 18q0 .052.003.104t.009.098q.011.315-.194.557q-.205.241-.514.241z");
}

</style>
