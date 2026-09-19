<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh-3m18qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="oh-3m18qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:milkshake" /></template>
