<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvekm43jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jvekm43jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tsunami-48" /></template>
