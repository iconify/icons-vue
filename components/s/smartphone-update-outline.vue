<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_8sl_z9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_8sl_z9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-update-outline" /></template>
