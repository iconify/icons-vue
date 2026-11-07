<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtjo_wb4r.css';
import '../../css/k/k26hh3b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtjo_wb4r"/><path class="k26hh3b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-bold-duotone" /></template>
