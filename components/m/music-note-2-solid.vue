<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3w_inz3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f3w_inz3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:music-note-2-solid" /></template>
