<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oms_6fbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="oms_6fbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:unlock" /></template>
