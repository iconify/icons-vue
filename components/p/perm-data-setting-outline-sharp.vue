<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhedzc6_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:perm-data-setting-outline-sharp" /></template>
<style>
.vhedzc6_c {
  fill: currentColor;
  d: path("M3 21L21 3v9.17q-.244-.11-.484-.2q-.241-.09-.516-.145V5.421L5.421 20h7.04q.093.262.199.509t.252.491zm2.421-1L20 5.421l-7.29 7.29zm12.502 1.77l-.107-.886q-.474-.105-.89-.32q-.416-.214-.749-.587l-.835.335l-.538-.816l.688-.577q-.165-.517-.165-1.035t.165-1.034l-.688-.577l.538-.815l.835.334q.314-.373.74-.587q.425-.215.899-.32l.107-.885h1l.108.884q.473.106.899.32t.74.588l.834-.334l.538.815l-.688.577q.165.517.165 1.035t-.165 1.034l.688.577l-.538.816l-.835-.335q-.332.373-.749.588q-.416.214-.89.32l-.107.884zm2.028-2.357q.626-.626.626-1.528t-.626-1.528t-1.528-.626t-1.528.626t-.626 1.528t.626 1.528t1.528.626t1.528-.626");
}

</style>
