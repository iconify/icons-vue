<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vss9qgb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vss9qgb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:oil" /></template>
