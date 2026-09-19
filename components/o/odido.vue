<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij4dl4bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij4dl4bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:odido" /></template>
