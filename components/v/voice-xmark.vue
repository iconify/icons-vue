<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psen4_kin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psen4_kin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:voice-xmark" /></template>
