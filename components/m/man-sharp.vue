<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o91nh_bfw.css';
import '../../css/h/h8fdi9bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="o91nh_bfw"/><path class="h8fdi9bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:man-sharp" /></template>
