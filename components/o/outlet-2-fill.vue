<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr_-pwids.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr_-pwids"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:outlet-2-fill" /></template>
