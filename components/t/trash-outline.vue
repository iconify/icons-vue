<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx8dsuc6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="bx8dsuc6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:trash-outline" /></template>
