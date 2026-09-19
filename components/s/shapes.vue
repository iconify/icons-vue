<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap76nacms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ap76nacms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:shapes" /></template>
