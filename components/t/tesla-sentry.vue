<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9t0qvb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9t0qvb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-sentry" /></template>
