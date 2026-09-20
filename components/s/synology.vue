<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi82rdd5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi82rdd5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:synology" /></template>
