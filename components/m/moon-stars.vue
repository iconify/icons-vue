<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6c4nob8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m6c4nob8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:moon-stars" /></template>
