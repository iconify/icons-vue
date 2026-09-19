<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bosxxmbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bosxxmbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:place-of-worship" /></template>
