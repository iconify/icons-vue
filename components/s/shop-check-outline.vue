<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsfxc0bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsfxc0bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shop-check-outline" /></template>
