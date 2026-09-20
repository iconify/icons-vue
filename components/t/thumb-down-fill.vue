<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9a5ey1ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9a5ey1ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thumb-down-fill" /></template>
