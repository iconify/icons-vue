<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voxbs0b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="voxbs0b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:plant-user-filled" /></template>
