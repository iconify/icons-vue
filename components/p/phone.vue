<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvh55wadc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pvh55wadc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:phone" /></template>
