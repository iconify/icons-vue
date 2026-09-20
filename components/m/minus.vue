<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap8ygib1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ap8ygib1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:minus" /></template>
