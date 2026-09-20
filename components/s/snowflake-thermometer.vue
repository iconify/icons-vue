<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jopy93b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jopy93b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:snowflake-thermometer" /></template>
