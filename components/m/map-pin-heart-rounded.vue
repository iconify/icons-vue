<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqh-8rb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map-pin-heart-rounded" /></template>
<style>
.nqh-8rb9z {
  fill: currentColor;
  d: path("M11.53 20.479q-.234-.077-.432-.25q-1.067-.981-2.164-2.185q-1.095-1.203-1.99-2.493t-1.468-2.633t-.572-2.622q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 1.279-.572 2.613q-.572 1.333-1.458 2.632q-.885 1.3-1.981 2.494T12.92 20.21q-.193.173-.44.26t-.481.086t-.47-.077m.47-6.737q1.177-1.076 1.803-1.705q.626-.63.98-1.048q.334-.42.468-.768t.134-.79q0-.766-.548-1.32q-.548-.553-1.306-.553q-.447 0-.861.182q-.415.182-.67.502q-.259-.32-.668-.503q-.409-.181-.87-.181q-.756 0-1.301.553q-.546.554-.546 1.32q0 .448.131.78t.456.756q.346.424.975 1.049T12 13.742");
}

</style>
