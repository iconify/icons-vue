<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7oiikgyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x7oiikgyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:telegram" /></template>
