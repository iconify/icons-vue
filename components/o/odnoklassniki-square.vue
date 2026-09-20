<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4aoj1bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i4aoj1bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:odnoklassniki-square" /></template>
