<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clvzz0bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="clvzz0bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:star" /></template>
