<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3-ztrbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3-ztrbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-10-box-outline" /></template>
