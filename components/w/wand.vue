<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzkmj9bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rzkmj9bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:wand" /></template>
