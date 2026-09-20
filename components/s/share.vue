<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbbc3r9uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jbbc3r9uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:share" /></template>
