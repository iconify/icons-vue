<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0umg59wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0umg59wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-shield-fill" /></template>
