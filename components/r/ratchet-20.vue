<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw6dnvbbs.css';
import '../../css/e/e2qan-08h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hw6dnvbbs"/><path class="e2qan-08h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ratchet-20" /></template>
