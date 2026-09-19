<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twtng14ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="twtng14ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thumbs-up-filled" /></template>
