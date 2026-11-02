<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwafqs80s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwafqs80s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:monitor-fill" /></template>
