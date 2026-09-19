<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shyve_bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shyve_bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thermometer" /></template>
