<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdf1uzbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdf1uzbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin" /></template>
