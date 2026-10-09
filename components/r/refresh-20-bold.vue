<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx9_9iq6d.css';
import '../../css/e/eumf_hb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lx9_9iq6d"/><path class="eumf_hb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refresh-20-bold" /></template>
