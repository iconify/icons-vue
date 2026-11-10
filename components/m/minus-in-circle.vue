<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj2vq8bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xj2vq8bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:minus-in-circle" /></template>
