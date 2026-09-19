<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2_kfxf2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2_kfxf2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:zap-off" /></template>
