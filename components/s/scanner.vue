<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4c9mb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ov4c9mb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:scanner" /></template>
