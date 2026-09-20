<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjyj_qbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tab-recent" /></template>
<style>
.tjyj_qbcv {
  fill: currentColor;
  d: path("m19.65 20.196l.546-.546l-1.811-1.811v-2.723h-.77v3.046zM13.77 9.04H20V6.616q0-.231-.192-.424T19.385 6h-5.616zm1.395 11.797Q14 19.67 14 18t1.165-2.835T18 14t2.836 1.165T22 18t-1.164 2.836T18 22t-2.835-1.164M4.615 19q-.69 0-1.152-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v6.159q-.644-.394-1.422-.584Q18.8 12 18.052 12q-2.496 0-4.255 1.752T12 18q0 .256.017.506t.072.494z");
}

</style>
