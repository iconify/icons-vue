<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6vxa-b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="e6vxa-b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ribbon" /></template>
