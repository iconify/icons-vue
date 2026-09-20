<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnolvzexl.css';
import '../../css/a/ag8wbubia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pnolvzexl"/><path class="ag8wbubia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:riot" /></template>
