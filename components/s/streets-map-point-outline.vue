<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-ejzngjy.css';
import '../../css/r/rc0x7kb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-ejzngjy"/><path class="rc0x7kb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-map-point-outline" /></template>
