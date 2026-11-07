<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpv5vhdla.css';
import '../../css/t/tpf4ahbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="tpf4ahbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-down-bold-duotone" /></template>
