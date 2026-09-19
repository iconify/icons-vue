<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z50j0q3zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="z50j0q3zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:triangle-solid-left-12" /></template>
