<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0ub5pikl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0ub5pikl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toggle-switch-off-outline" /></template>
