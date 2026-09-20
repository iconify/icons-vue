<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sslt314qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sslt314qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:support" /></template>
