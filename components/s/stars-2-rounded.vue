<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3149y26b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stars-2-rounded" /></template>
<style>
.k3149y26b {
  fill: currentColor;
  d: path("m12 17.275l-4.15 2.5q-.275.175-.575.15t-.525-.2t-.35-.437t-.05-.588l1.1-4.725L3.775 10.8q-.25-.225-.312-.513t.037-.562t.3-.45t.55-.225l4.85-.425l1.875-4.45q.125-.3.388-.45t.537-.15t.537.15t.388.45l1.875 4.45l4.85.425q.35.05.55.225t.3.45t.038.563t-.313.512l-3.675 3.175l1.1 4.725q.075.325-.05.588t-.35.437t-.525.2t-.575-.15zm7.25-11.45l-1.5.875q-.15.075-.288-.012t-.087-.263l.4-1.65l-1.325-1.1q-.125-.125-.075-.262t.225-.163l1.75-.15l.675-1.575q.05-.15.225-.15t.225.15L20.15 3.1l1.75.15q.175.025.225.163t-.075.262l-1.325 1.1l.4 1.65q.05.175-.087.263t-.288.012z");
}

</style>
