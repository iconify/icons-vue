<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffdwxrmjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ffdwxrmjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:phone-arrow-up-right" /></template>
