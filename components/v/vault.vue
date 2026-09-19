<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd48whbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fd48whbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:vault" /></template>
