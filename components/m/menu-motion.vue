<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgwm_-bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgwm_-bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-motion" /></template>
