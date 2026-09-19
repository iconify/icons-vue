<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_3appbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i_3appbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:weight-hanging" /></template>
