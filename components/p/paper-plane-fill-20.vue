<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj9rxse9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lj9rxse9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:paper-plane-fill-20" /></template>
