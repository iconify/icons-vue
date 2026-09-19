<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfdub7buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dfdub7buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:read-me" /></template>
