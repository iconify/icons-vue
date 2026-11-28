<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz1rqjboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz1rqjboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:traffic-cone-solid" /></template>
