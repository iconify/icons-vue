<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv9xr--ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv9xr--ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mikrotik" /></template>
