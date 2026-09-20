<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm80p_y1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sm80p_y1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:notification" /></template>
