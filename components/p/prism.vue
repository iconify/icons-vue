<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2bp27bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2bp27bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:prism" /></template>
