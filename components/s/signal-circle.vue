<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl297vo_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wl297vo_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:signal-circle" /></template>
