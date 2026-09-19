<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aswzxcjfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aswzxcjfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:welcome-add-page" /></template>
