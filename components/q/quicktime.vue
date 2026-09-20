<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm_1i27sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm_1i27sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:quicktime" /></template>
