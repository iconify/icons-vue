<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry3ti9y4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry3ti9y4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:markup-fill" /></template>
