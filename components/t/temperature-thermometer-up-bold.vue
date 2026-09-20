<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-yl0srap.css';
import '../../css/f/fexna311s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-yl0srap"/><path class="fexna311s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:temperature-thermometer-up-bold" /></template>
