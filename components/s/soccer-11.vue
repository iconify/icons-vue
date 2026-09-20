<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfo2c8bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="nfo2c8bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:soccer-11" /></template>
