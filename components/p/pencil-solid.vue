<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj8hsacgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lj8hsacgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pencil-solid" /></template>
