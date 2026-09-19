<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4a-oac3f.css';
import '../../css/k/klwyf98zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q4a-oac3f"/><path class="klwyf98zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:trending-down-sharp" /></template>
