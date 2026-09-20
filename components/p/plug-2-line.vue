<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_l-v3ilc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_l-v3ilc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:plug-2-line" /></template>
