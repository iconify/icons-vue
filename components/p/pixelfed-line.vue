<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy931_b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy931_b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pixelfed-line" /></template>
