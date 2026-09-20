<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5t-u2bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5t-u2bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-cellular-3-line" /></template>
