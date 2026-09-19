<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejnf3c28v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ejnf3c28v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:svg" /></template>
