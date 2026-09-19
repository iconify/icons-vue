<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4mm9rbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b4mm9rbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:upwork" /></template>
