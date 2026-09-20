<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1jccw92g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1jccw92g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-1-warning" /></template>
