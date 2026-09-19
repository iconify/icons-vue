<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t68k2db2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="t68k2db2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-square" /></template>
