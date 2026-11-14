<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft5y08bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pumpkin" /></template>
<style>
.ft5y08bdd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.801 6.213q4.524-.087 6.826 2.543q2.107 2.408 1.615 5.85Q20.365 20.75 12 20.75q.149 0 .287-.057t.243-.163Q15 18.061 15 13.5t-2.47-7.03q-.105-.106-.243-.163T12 6.25t-.287.057t-.243.163Q9 8.939 9 13.5t2.47 7.03q.105.105.242.162t.286.058q-8.363-.001-9.24-6.144q-.492-3.442 1.615-5.85Q6.697 6.1 11.287 6.215q.27-2.691 2.476-3.427q.07-.023.143-.032t.147-.004t.145.025t.137.052t.125.079t.107.101t.085.12t.06.134q.047.141.036.29q-.01.149-.077.282q-.067.134-.18.232q-.112.097-.254.145q-1.212.403-1.436 2.001M12 18.862q1.5-1.976 1.5-5.362T12 8.138q-1.5 1.976-1.5 5.362t1.5 5.362");
}

</style>
