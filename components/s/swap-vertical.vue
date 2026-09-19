<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-2skvf2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-2skvf2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:swap-vertical" /></template>
