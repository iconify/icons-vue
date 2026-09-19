<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi_4ffb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bi_4ffb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:square-slash" /></template>
