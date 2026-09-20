<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xemtl5mfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xemtl5mfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticky-note-minus" /></template>
