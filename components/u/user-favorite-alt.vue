<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-fl9tbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t-fl9tbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-favorite-alt" /></template>
