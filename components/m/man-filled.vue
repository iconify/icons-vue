<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdw-doqfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdw-doqfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:man-filled" /></template>
