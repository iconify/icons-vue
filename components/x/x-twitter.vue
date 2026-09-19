<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7i5xtbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p7i5xtbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:x-twitter" /></template>
