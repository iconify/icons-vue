<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj89ikdob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dj89ikdob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:move-one" /></template>
