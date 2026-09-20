<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcbly9b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:power-settings-new-outline-rounded" /></template>
<style>
.gcbly9b_q {
  fill: currentColor;
  d: path("M12.003 21q-1.866 0-3.51-.709q-1.643-.708-2.859-1.923T3.709 15.51T3 12q0-1.748.613-3.29q.612-1.54 1.706-2.745q.16-.177.346-.161t.326.15t.17.333t-.147.392q-.935 1.063-1.475 2.424Q4 10.464 4 12q0 3.35 2.325 5.675T12 20t5.675-2.325T20 12q0-1.54-.54-2.899q-.539-1.359-1.474-2.422q-.177-.195-.147-.393t.17-.332t.327-.15q.185-.016.345.161q1.094 1.204 1.707 2.745Q21 10.253 21 12q0 1.868-.708 3.51t-1.924 2.858t-2.856 1.923t-3.509.709m-.36-8.144q-.143-.143-.143-.356v-9q0-.213.144-.356T12.001 3t.356.144t.143.356v9q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
