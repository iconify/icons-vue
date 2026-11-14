<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv_472_6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:souvenir" /></template>
<style>
.dv_472_6q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.787 10.221q-.243 2.565.958 4.723q-.981.404-1.321 1.649l-.545 2q-.324 1.192.426 2.174q.75.983 1.986.983h13.418q1.236 0 1.986-.983q.75-.982.426-2.174l-.545-2q-.34-1.245-1.321-1.649q1.201-2.158.958-4.723q-.301-3.177-2.662-5.324T12 2.75q-3.191 0-5.551 2.147t-2.662 5.324m13.827 4.529H12.75v-1h.294q1.325 0 1.968-1.159q.642-1.16-.06-2.284l-1.044-1.67Q13.247 7.58 12 7.58t-1.908 1.057v.001l-1.044 1.669q-.702 1.124-.06 2.284q.643 1.159 1.968 1.159h.294v1H6.386q-1.335-1.974-1.106-4.388q.247-2.599 2.178-4.355T12 4.25t4.542 1.757q1.931 1.756 2.178 4.355q.229 2.414-1.106 4.388");
}

</style>
