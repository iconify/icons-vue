<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8pjv5b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="y8pjv5b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:volume-up" /></template>
