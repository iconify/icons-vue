<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vab42o9le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vab42o9le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pterodactyl" /></template>
