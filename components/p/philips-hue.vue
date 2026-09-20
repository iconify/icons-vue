<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx6x4gb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx6x4gb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:philips-hue" /></template>
