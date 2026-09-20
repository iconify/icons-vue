<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/antp0sy-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="antp0sy-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:minus-square-o" /></template>
