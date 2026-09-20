<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys0ffgblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys0ffgblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sql-query" /></template>
