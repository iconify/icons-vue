<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pepi70ffa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pepi70ffa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:water-sanitation" /></template>
