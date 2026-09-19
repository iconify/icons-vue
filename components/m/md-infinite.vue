<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tutwf7z4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tutwf7z4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-infinite" /></template>
