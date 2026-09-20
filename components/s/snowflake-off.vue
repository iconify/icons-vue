<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy_c_3btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy_c_3btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:snowflake-off" /></template>
