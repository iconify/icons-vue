<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgqpeab4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgqpeab4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:service-toolbox" /></template>
