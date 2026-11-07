<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-cbzraid.css';
import '../../css/f/f3r88-jzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-cbzraid"/><path clip-rule="evenodd" class="f3r88-jzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:point-on-map-bold-duotone" /></template>
