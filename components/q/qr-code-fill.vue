<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr-x4e2ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr-x4e2ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:qr-code-fill" /></template>
