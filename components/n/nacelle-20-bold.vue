<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9w0v0j8h.css';
import '../../css/k/kyt7f6bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n9w0v0j8h"/><path class="kyt7f6bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nacelle-20-bold" /></template>
