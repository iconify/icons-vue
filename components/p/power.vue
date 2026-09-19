<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od5v46b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="od5v46b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:power" /></template>
