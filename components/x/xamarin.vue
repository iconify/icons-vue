<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmodh8b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmodh8b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:xamarin" /></template>
