<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4412r2nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i4412r2nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:reply" /></template>
