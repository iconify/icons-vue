<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgnp9cbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cgnp9cbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-slash-solid" /></template>
