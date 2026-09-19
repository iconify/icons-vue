<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6zq0m34v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d6zq0m34v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:meter-alt" /></template>
