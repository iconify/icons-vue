<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgq-_yb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgq-_yb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:system76-light" /></template>
