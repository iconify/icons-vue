<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9rz7-b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9rz7-b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-difference" /></template>
