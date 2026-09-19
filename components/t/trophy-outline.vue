<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/viq1-by_c.css';
import '../../css/n/nskm8xyiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="viq1-by_c"/><path class="nskm8xyiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:trophy-outline" /></template>
