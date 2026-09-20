<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exa37_tip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exa37_tip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:settings-2-line" /></template>
