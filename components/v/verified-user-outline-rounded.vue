<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekie_ebyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:verified-user-outline-rounded" /></template>
<style>
.ekie_ebyj {
  fill: currentColor;
  d: path("m10.95 13.43l-1.784-1.784q-.147-.146-.345-.155t-.363.155t-.166.357t.166.357l1.927 1.932q.242.243.565.243t.566-.243l4.038-4.038q.146-.146.156-.347t-.156-.366t-.357-.166t-.356.166zm.764 7.387q-.15-.025-.281-.075q-2.952-1.125-4.692-3.816T5 11.1V6.817q0-.51.295-.923t.755-.6l5.385-2q.292-.106.565-.106t.566.106l5.384 2q.46.187.755.6t.295.923V11.1q0 3.135-1.74 5.826t-4.693 3.816q-.13.05-.28.075t-.287.025t-.287-.025M12 19.9q2.6-.825 4.3-3.3t1.7-5.5V6.798q0-.192-.106-.346q-.105-.154-.298-.23l-5.384-2q-.096-.04-.212-.04t-.212.04l-5.384 2q-.193.076-.298.23Q6 6.606 6 6.798V11.1q0 3.025 1.7 5.5t4.3 3.3m0-7.861");
}

</style>
