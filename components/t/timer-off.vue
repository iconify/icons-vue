<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrlku7btj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrlku7btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:timer-off" /></template>
