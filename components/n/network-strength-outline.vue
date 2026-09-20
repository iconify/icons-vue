<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn8k5hbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn8k5hbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-strength-outline" /></template>
