<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr1w4fuup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr1w4fuup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:saucelabs" /></template>
