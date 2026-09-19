<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v38kukb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v38kukb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-font" /></template>
