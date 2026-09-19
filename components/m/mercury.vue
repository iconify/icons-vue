<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llq7qvbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1792};
const content = `<path class="llq7qvbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:mercury" /></template>
