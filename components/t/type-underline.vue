<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6dhtabtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j6dhtabtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:type-underline" /></template>
