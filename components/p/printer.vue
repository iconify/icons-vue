<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sfdv74bik.css';
import '../../css/m/medbz2b1j.css';
import '../../css/r/rfgv0sb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="rotate(-90 10.5 8.5)" class="bi12bsetm"><path class="sfdv74bik"/><path class="medbz2b1j"/><circle class="rfgv0sb9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:printer" /></template>
