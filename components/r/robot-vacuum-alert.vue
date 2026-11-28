<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5abtxetp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5abtxetp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:robot-vacuum-alert" /></template>
