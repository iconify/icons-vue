<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax4chccyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ax4chccyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microscope" /></template>
