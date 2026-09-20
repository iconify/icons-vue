<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6jnxwbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6jnxwbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tablet-mac" /></template>
