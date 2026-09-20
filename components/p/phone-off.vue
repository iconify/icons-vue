<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1s0jpbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1s0jpbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-off" /></template>
