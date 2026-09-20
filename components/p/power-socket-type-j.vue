<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-e5j90ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-e5j90ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-socket-type-j" /></template>
