<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9xfwac2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f9xfwac2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-feedback" /></template>
