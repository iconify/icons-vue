<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekkxjwbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekkxjwbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:strikethrough" /></template>
