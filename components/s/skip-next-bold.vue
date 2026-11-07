<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdhe4sbui.css';
import '../../css/x/xv7by3x_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdhe4sbui"/><path class="xv7by3x_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skip-next-bold" /></template>
