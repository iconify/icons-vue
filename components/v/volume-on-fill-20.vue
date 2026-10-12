<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih1h7z2gg.css';
import '../../css/l/l_7m7z2gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ih1h7z2gg"/><path class="l_7m7z2gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-on-fill-20" /></template>
