<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab0zmzbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab0zmzbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sim-card-warning-line" /></template>
