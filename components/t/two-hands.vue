<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d03hiccvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d03hiccvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:two-hands" /></template>
