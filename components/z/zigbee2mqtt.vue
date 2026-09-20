<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9__3c02i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9__3c02i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zigbee2mqtt" /></template>
