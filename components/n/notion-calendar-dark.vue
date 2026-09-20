<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alpcz-bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="alpcz-bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notion-calendar-dark" /></template>
