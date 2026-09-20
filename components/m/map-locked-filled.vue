<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noywm2ubs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noywm2ubs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-locked-filled" /></template>
