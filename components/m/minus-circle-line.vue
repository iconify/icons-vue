<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw1dwtm4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw1dwtm4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:minus-circle-line" /></template>
