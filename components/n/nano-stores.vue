<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb11dvb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hb11dvb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nano-stores" /></template>
