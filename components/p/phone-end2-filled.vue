<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4ha_dcsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4ha_dcsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:phone-end2-filled" /></template>
