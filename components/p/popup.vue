<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgwpg6btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1091,"height":1000};
const content = `<path class="qgwpg6btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:popup" /></template>
