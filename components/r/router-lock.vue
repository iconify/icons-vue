<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixom8kbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixom8kbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:router-lock" /></template>
