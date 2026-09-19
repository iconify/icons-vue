<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajy8mmfuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ajy8mmfuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:search-locate-mirror" /></template>
