<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er0e4cwyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er0e4cwyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:paragraphs-indent" /></template>
