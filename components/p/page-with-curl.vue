<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z23109bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z23109bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:page-with-curl" /></template>
