<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8vby9b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1856,"height":1664};
const content = `<path class="j8vby9b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:warning" /></template>
