<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvfm5p4nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jvfm5p4nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:meatballs-v" /></template>
