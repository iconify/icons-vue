<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu5gjko1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="lu5gjko1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:tacos" /></template>
