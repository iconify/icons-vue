<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_3xo-zcn.css';
import '../../css/f/fy8hrfkoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_3xo-zcn"/><path class="fy8hrfkoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skyscraper-48-bold" /></template>
