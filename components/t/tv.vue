<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arx8vnbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="arx8vnbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:tv" /></template>
