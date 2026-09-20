<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8xpc2b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8xpc2b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-shipping" /></template>
