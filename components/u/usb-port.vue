<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q574zqbqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q574zqbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:usb-port" /></template>
