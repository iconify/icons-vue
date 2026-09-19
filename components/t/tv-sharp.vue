<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1u8gz3hx.css';
import '../../css/g/gdktam-6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1u8gz3hx"/><rect class="gdktam-6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:tv-sharp" /></template>
