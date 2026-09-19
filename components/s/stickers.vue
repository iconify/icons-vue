<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfb048mnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mfb048mnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:stickers" /></template>
