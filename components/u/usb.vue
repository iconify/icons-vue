<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjfd1vynk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfd1vynk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:usb" /></template>
