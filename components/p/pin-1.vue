<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slo_ucbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slo_ucbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pin-1" /></template>
