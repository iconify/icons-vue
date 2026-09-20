<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgh92ubxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgh92ubxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-frame-filled" /></template>
