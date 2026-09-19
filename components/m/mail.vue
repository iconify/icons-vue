<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in9z5hbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="in9z5hbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:mail" /></template>
