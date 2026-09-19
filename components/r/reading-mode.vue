<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv5zop4pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mv5zop4pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:reading-mode" /></template>
