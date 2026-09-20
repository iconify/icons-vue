<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppxf_y04o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppxf_y04o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:router-wireless-off" /></template>
