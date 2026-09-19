<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhr5dqnme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rhr5dqnme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:sphere" /></template>
