<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh3-hqbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gh3-hqbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sad-cry" /></template>
