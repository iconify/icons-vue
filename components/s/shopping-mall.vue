<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-m87dbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="l-m87dbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:shopping-mall" /></template>
