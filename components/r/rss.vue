<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du0059b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="du0059b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:rss" /></template>
