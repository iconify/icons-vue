<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cui0wbciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cui0wbciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:paragraphs-indent-left" /></template>
