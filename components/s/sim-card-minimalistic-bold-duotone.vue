<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-vry1bva.css';
import '../../css/m/m-4cng7zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-vry1bva"/><path class="m-4cng7zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-card-minimalistic-bold-duotone" /></template>
