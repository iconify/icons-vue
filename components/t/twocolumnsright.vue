<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x03szrc6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="x03szrc6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:twocolumnsright" /></template>
