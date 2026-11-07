<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp7j5gwce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp7j5gwce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rolling-pin-broken" /></template>
