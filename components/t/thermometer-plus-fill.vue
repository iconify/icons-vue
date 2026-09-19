<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqy0_y_xf.css';
import '../../css/w/w4-6i1bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="qqy0_y_xf"/><rect transform="rotate(-90 5 6)" class="qqy0_y_xf"/><path class="w4-6i1bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:thermometer-plus-fill" /></template>
