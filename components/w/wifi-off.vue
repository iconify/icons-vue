<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n87gr3g_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n87gr3g_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:wifi-off" /></template>
