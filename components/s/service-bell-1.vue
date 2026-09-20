<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frvq3h_2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="frvq3h_2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:service-bell-1" /></template>
