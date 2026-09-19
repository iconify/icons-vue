<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwcburvae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1024};
const content = `<path class="rwcburvae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:raspberrypi" /></template>
