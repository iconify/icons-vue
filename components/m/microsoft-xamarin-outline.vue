<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi9fd7blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi9fd7blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-xamarin-outline" /></template>
