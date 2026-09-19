<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u66q5t6jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":432};
const content = `<path class="u66q5t6jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:notifications-none" /></template>
