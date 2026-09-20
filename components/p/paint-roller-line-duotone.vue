<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fme7zr9sh.css';
import '../../css/k/k9mlok3zo.css';
import '../../css/f/ff9gj-ppn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fme7zr9sh"/><path class="k9mlok3zo"/><path class="ff9gj-ppn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-roller-line-duotone" /></template>
