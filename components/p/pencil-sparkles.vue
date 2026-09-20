<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt8gb5tzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt8gb5tzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pencil-sparkles" /></template>
