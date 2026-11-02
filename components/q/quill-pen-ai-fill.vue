<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tee2pe44x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tee2pe44x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:quill-pen-ai-fill" /></template>
