<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl6t_4w4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hl6t_4w4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openhab-dark" /></template>
