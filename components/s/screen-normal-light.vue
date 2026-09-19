<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm_iszbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm_iszbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:screen-normal-light" /></template>
