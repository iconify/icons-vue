<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn9n7-baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fn9n7-baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tornado-48-bold" /></template>
