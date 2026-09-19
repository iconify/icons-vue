<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh_c97dbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh_c97dbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shelly-logo" /></template>
