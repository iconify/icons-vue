<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_yax-h2e.css';
import '../../css/d/d8q64recs.css';
import '../../css/f/ft5pk3bco.css';
import '../../css/t/t13pyabps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g_yax-h2e"/><path class="d8q64recs"/><path class="ft5pk3bco"/><path class="t13pyabps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mic-off-20" /></template>
