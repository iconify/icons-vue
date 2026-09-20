<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x12s0fb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x12s0fb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pipette-outline" /></template>
