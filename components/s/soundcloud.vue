<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h60wulb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="h60wulb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:soundcloud" /></template>
