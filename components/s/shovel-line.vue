<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ictq4bc4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ictq4bc4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shovel-line" /></template>
