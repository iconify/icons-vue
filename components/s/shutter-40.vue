<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfr8ntbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfr8ntbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:shutter-40" /></template>
