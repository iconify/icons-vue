<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4y_w4s9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4y_w4s9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:streamplay-logo" /></template>
