<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw5d_zbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw5d_zbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tunnel-outline" /></template>
