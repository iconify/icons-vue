<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcouut1tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phishing-outline-rounded" /></template>
<style>
.kcouut1tp {
  fill: currentColor;
  d: path("M7.471 18.471Q6 16.942 6 14.788V11.2q0-.273.252-.379t.444.106l2.527 2.585q.14.14.14.331t-.14.338q-.146.146-.347.146t-.347-.146L7 12.594v2.195q0 1.727 1.185 2.969Q9.369 19 11.077 19t2.892-1.242q1.185-1.242 1.185-2.97v-3.367q-.804-.177-1.325-.805q-.521-.627-.521-1.462t.511-1.472t1.335-.815V3.5q0-.213.143-.357q.144-.143.357-.143t.357.143t.143.357v3.367q.823.177 1.334.815T18 9.154t-.512 1.465t-1.334.802v3.368q0 2.153-1.471 3.682T11.077 20t-3.606-1.529m9.136-8.364Q17 9.714 17 9.154t-.393-.953t-.953-.393t-.953.393t-.393.953t.393.953t.953.393t.953-.393m-.953-.953");
}

</style>
