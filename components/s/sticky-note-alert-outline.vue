<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/did9inf2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="did9inf2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticky-note-alert-outline" /></template>
