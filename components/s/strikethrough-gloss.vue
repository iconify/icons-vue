<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by7fs_z4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by7fs_z4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:strikethrough-gloss" /></template>
