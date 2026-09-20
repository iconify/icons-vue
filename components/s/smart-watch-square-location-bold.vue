<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzlnpvced.css';
import '../../css/v/vmfgchi1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzlnpvced"/><path class="vmfgchi1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smart-watch-square-location-bold" /></template>
