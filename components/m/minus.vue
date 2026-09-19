<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6jkanb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s6jkanb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:minus" /></template>
