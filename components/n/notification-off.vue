<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h68a5vtzz.css';
import '../../css/w/wm0dbbbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="h68a5vtzz"/><path class="wm0dbbbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:notification-off" /></template>
