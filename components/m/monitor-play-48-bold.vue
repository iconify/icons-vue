<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw2mmrfxt.css';
import '../../css/p/phox42bnd.css';
import '../../css/q/q8ft2nb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kw2mmrfxt"/><path class="phox42bnd"/><path class="q8ft2nb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-play-48-bold" /></template>
