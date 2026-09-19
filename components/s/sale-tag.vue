<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoegt1bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":496};
const content = `<path class="yoegt1bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sale-tag" /></template>
