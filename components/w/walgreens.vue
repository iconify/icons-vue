<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llx_gbc1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":335.72,"height":217.4};
const content = `<path class="llx_gbc1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:walgreens" /></template>
