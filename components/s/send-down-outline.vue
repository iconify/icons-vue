<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf-y_r2sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kf-y_r2sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-down-outline" /></template>
