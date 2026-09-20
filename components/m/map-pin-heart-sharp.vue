<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k57tjkbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map-pin-heart-sharp" /></template>
<style>
.k57tjkbgp {
  fill: currentColor;
  d: path("M12 21.02q-3.525-3.118-5.31-5.815q-1.786-2.697-1.786-4.909q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 2.212-1.785 4.909q-1.786 2.697-5.311 5.814m0-7.277q1.177-1.077 1.803-1.706q.626-.628.98-1.048q.334-.419.468-.767t.134-.79q0-.767-.548-1.32t-1.306-.553q-.447 0-.861.181q-.415.182-.67.503q-.259-.32-.668-.503q-.409-.181-.87-.181q-.756 0-1.301.553q-.546.554-.546 1.32q0 .448.131.78t.456.756q.346.423.975 1.048T12 13.742");
}

</style>
