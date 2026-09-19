<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx9gfpabu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nx9gfpabu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:theme" /></template>
