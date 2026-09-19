<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef53n3xnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ef53n3xnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:screenpal" /></template>
