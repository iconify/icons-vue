<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tza8uod_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tza8uod_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-vacuum-variant-off" /></template>
