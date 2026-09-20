<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_wdpsipy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t_wdpsipy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:one-finger-drag-horizontal-solid" /></template>
