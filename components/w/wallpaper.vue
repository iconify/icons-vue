<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8fkkvm0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="s8fkkvm0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wallpaper" /></template>
