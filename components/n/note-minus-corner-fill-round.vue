<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9xhb4b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9xhb4b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-minus-corner-fill-round" /></template>
