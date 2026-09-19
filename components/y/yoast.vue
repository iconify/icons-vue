<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zplytfi9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zplytfi9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:yoast" /></template>
