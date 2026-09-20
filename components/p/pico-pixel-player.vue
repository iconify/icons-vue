<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzuu6qb5w.css';
import '../../css/z/zjgo95xol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzuu6qb5w"/><path class="zjgo95xol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pico-pixel-player" /></template>
