<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa_ajzbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="qa_ajzbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pictures-f" /></template>
