<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfoildnck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="pfoildnck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:squarespace" /></template>
