<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx1swky9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yx1swky9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:review-solid" /></template>
