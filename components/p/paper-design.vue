<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw4v21b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw4v21b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:paper-design" /></template>
