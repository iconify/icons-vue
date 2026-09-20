<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxvwipb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxvwipb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:post-it-note-text" /></template>
