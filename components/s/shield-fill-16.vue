<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huwzlxbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="huwzlxbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shield-fill-16" /></template>
