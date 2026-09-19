<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko_3_kw6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ko_3_kw6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:pen-to-square" /></template>
