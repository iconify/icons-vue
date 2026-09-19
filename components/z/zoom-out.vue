<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmpx80b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":384};
const content = `<path class="tmpx80b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:zoom-out" /></template>
