<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njmo_acwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="njmo_acwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:pin-off" /></template>
