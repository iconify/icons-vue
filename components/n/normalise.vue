<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8dnzwbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r8dnzwbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:normalise" /></template>
