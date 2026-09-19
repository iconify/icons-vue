<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb0k1pbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nb0k1pbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:table" /></template>
