<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd9-tny0x.css';
import '../../css/n/ndt9adc_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cd9-tny0x"/><path class="ndt9adc_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sqlalchemy-wordmark" /></template>
