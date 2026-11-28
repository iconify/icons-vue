<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abu8hlbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abu8hlbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:users-minus" /></template>
