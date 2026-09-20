<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svie05b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svie05b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:usb-square-filled" /></template>
