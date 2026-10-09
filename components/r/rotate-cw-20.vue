<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht0kv9akh.css';
import '../../css/x/xl70_ubev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ht0kv9akh"/><path class="xl70_ubev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotate-cw-20" /></template>
