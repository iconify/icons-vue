<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8j21qb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="i8j21qb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:scroll" /></template>
