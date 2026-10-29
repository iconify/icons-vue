<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2qslhbnv.css';
import '../../css/h/h8poafcho.css';
import '../../css/d/dh2skybyq.css';
import '../../css/u/ub3e2sbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2qslhbnv"/><path class="h8poafcho"/><path class="dh2skybyq"/><path class="ub3e2sbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:usb" /></template>
