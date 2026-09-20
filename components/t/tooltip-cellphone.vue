<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu7ancbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu7ancbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-cellphone" /></template>
