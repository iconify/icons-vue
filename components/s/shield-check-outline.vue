<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk677ab6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk677ab6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-check-outline" /></template>
