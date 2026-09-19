<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddoxlnb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ddoxlnb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:restroom" /></template>
