<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vblmr_zyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vblmr_zyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:triangle-fill" /></template>
