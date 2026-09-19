<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy2xwebtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sy2xwebtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:typescript" /></template>
