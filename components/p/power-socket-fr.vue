<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f528pub4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f528pub4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-socket-fr" /></template>
