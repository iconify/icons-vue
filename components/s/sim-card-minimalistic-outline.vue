<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_m-zf91d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_m-zf91d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-card-minimalistic-outline" /></template>
