<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpv54j2pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mpv54j2pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:phone-vibrate-solid" /></template>
