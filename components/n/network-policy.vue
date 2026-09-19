<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2_mk1czl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2_mk1czl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:network-policy" /></template>
