<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba680n3we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ba680n3we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-arrows-expand" /></template>
