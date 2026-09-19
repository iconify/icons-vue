<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kemw-9b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kemw-9b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rectangle-stack-solid" /></template>
