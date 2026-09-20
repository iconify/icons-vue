<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1s_2gu_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1s_2gu_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:star-off-fill" /></template>
