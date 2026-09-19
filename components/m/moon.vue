<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fje1h4byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fje1h4byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:moon" /></template>
