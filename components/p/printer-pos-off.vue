<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiz7z0ihj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiz7z0ihj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-pos-off" /></template>
