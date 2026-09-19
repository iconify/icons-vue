<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1tfhvw2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u1tfhvw2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:uneditable-2-mirrored" /></template>
