<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df1n7oboy.css';
import '../../css/a/a_knjioaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="df1n7oboy"/><path class="a_knjioaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plus-48" /></template>
