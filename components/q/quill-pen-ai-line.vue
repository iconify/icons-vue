<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzvdysbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzvdysbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quill-pen-ai-line" /></template>
