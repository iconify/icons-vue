<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxdr6dbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="mxdr6dbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:output" /></template>
