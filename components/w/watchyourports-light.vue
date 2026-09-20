<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhdoorb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xhdoorb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:watchyourports-light" /></template>
