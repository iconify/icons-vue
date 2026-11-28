<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8wzusbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8wzusbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tv-off" /></template>
