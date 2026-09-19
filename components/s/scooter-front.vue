<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brrzp7bqp.css';
import '../../css/y/yswlpl_1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="brrzp7bqp"/><path class="yswlpl_1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:scooter-front" /></template>
