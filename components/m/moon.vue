<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd0x4bpta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pd0x4bpta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:moon" /></template>
