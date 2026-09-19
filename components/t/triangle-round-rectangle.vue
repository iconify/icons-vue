<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9rz2pk3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m9rz2pk3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:triangle-round-rectangle" /></template>
