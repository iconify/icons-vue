<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaoqydbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uaoqydbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:messenger-fill-12" /></template>
