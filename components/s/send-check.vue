<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ruscb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ruscb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:send-check" /></template>
