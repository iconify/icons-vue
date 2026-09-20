<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbqsksbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbqsksbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pipette-linear" /></template>
