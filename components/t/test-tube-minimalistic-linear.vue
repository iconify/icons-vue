<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq3gmebpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq3gmebpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:test-tube-minimalistic-linear" /></template>
