<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrio91b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrio91b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sticky-note-2-line" /></template>
