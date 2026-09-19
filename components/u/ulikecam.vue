<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx1xxj1an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rx1xxj1an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:ulikecam" /></template>
