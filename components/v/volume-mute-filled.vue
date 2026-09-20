<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slzco6b1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slzco6b1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volume-mute-filled" /></template>
