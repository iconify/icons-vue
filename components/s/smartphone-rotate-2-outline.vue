<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3-qgwb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3-qgwb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-rotate-2-outline" /></template>
