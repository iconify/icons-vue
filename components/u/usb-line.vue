<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp6_omz3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp6_omz3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:usb-line" /></template>
