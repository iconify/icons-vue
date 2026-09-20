<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7j5rbdjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j7j5rbdjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:meatballs-h" /></template>
