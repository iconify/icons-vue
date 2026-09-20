<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clz8sab3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="clz8sab3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-2-bold" /></template>
