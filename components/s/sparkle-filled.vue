<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn1b_0v6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jn1b_0v6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:sparkle-filled" /></template>
