<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzpemx0rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hzpemx0rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:ticket-fill-20" /></template>
