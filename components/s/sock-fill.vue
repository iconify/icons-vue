<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gey1e15eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gey1e15eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sock-fill" /></template>
