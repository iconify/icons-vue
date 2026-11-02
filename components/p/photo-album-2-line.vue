<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1agfybop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1agfybop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:photo-album-2-line" /></template>
