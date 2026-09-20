<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0orl9v2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0orl9v2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:usb-flash-disk-line" /></template>
