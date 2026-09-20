<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsk3tsbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dsk3tsbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:ring" /></template>
