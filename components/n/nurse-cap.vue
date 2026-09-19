<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5l4n3dug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e5l4n3dug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:nurse-cap" /></template>
