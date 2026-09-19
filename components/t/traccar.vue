<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk0w-6brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk0w-6brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:traccar" /></template>
