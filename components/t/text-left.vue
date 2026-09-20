<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1wd0cdzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x1wd0cdzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:text-left" /></template>
