<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0g_tgh1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x0g_tgh1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pacman-solid" /></template>
