<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtp5fgbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtp5fgbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sticky-note-2-fill" /></template>
