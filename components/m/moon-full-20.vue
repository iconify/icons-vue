<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suk0u9b4j.css';
import '../../css/v/vrixi1pns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="suk0u9b4j"/><path class="vrixi1pns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-full-20" /></template>
