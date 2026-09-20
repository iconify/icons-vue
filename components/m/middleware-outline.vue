<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi5qpp_-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi5qpp_-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:middleware-outline" /></template>
