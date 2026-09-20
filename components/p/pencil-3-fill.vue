<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr0lscbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr0lscbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-3-fill" /></template>
