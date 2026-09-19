<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8j8t-uam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="j8j8t-uam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:users" /></template>
