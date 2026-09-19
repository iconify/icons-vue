<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjzmodb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sjzmodb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:scorpio" /></template>
