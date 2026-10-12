<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p7r3bok2a.css';
import '../../css/t/tiefb7boe.css';
import '../../css/q/qnm-tdbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p7r3bok2a"/><path class="tiefb7boe"/><path class="qnm-tdbsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:milk-duotone" /></template>
