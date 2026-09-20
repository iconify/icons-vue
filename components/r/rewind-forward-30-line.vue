<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjn112btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjn112btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-30-line" /></template>
