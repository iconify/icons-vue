<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0x3p_9pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0x3p_9pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:night-wind-2" /></template>
