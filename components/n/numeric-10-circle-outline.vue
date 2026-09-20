<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxvdnobkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxvdnobkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-10-circle-outline" /></template>
