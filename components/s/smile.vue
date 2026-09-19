<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rywd8ybxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="rywd8ybxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:smile" /></template>
