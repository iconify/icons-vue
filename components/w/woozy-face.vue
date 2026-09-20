<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl06zb7mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yl06zb7mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:woozy-face" /></template>
