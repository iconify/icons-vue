<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlvaks1du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlvaks1du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:umbrella-closed-outline" /></template>
