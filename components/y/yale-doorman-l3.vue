<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha_y7ohok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha_y7ohok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:yale-doorman-l3" /></template>
