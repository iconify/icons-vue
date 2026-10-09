<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjugphbbc.css';
import '../../css/u/u5yldcb3g.css';
import '../../css/f/fip9ksb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vjugphbbc"/><path class="u5yldcb3g"/><path class="fip9ksb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-star-48" /></template>
