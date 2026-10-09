<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg4jgbz7f.css';
import '../../css/b/bfg6oocam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lg4jgbz7f"/><path class="bfg6oocam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:street-light-20" /></template>
