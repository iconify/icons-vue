<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocf6fy74a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ocf6fy74a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:printer" /></template>
