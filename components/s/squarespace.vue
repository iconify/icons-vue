<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7w5snbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7w5snbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:squarespace" /></template>
