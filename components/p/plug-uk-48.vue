<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8w6b6l9s.css';
import '../../css/i/i1aaxkb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a8w6b6l9s"/><path class="i1aaxkb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plug-uk-48" /></template>
