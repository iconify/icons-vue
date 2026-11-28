<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8-858bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8-858bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shield-lock" /></template>
