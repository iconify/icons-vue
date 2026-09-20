<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh7axibfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh7axibfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-horizontal-filled" /></template>
