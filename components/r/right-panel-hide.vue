<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir5tzud0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ir5tzud0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:right-panel-hide" /></template>
