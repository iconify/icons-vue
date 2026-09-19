<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nikx1gbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nikx1gbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:terminal" /></template>
