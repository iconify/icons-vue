<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txayfw-gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txayfw-gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:retro-achievements" /></template>
