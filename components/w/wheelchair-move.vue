<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0fqe3bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="e0fqe3bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:wheelchair-move" /></template>
