<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4ihldyvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c4ihldyvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shield-fill-check" /></template>
