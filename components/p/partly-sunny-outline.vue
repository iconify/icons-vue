<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htohhkvke.css';
import '../../css/b/bixpb61-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="htohhkvke"/><path class="bixpb61-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:partly-sunny-outline" /></template>
