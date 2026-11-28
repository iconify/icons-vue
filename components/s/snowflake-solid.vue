<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv8lb0fxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv8lb0fxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:snowflake-solid" /></template>
