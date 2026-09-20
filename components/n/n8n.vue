<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm-xvnbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":228,"height":120};
const content = `<path clip-rule="evenodd" class="wm-xvnbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:n8n" /></template>
