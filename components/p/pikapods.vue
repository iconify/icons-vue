<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tufwuf_6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tufwuf_6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pikapods" /></template>
