<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz29c9t9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uz29c9t9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:right-arrow" /></template>
