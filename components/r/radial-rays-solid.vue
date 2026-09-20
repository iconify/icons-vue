<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk92eoj1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk92eoj1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:radial-rays-solid" /></template>
