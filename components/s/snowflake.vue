<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1127jm3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1127jm3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:snowflake" /></template>
