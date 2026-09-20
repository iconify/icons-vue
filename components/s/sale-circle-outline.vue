<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjmc-obmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjmc-obmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sale-circle-outline" /></template>
