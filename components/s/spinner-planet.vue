<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eelx_9v_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eelx_9v_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:spinner-planet" /></template>
