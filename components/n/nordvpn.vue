<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh4l7dhqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh4l7dhqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nordvpn" /></template>
