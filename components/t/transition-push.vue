<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezj_jlboy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ezj_jlboy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:transition-push" /></template>
