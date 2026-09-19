<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-hb8rb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-hb8rb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:vibrate-off" /></template>
