<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upsw8zbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="upsw8zbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:open-file-folder" /></template>
