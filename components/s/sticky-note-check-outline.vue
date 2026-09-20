<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjbarccmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjbarccmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticky-note-check-outline" /></template>
