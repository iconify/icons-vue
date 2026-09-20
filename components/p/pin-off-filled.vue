<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymol9uw0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymol9uw0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-off-filled" /></template>
