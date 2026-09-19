<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjjw42d6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kjjw42d6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:themeco" /></template>
