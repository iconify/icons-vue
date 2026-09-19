<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skdtm7eru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="skdtm7eru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:paved-road-alt-outline" /></template>
