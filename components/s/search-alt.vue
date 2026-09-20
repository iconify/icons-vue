<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc8bcyg6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bc8bcyg6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:search-alt" /></template>
