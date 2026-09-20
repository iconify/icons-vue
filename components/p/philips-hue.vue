<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kochng6qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kochng6qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:philips-hue" /></template>
