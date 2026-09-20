<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpb7yibku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tpb7yibku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teleport" /></template>
