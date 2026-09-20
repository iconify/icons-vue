<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixj8ylb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ixj8ylb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:speaker-2-remix" /></template>
