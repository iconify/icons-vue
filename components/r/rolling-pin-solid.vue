<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcaniacwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcaniacwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rolling-pin-solid" /></template>
