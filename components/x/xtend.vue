<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwr78-bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwr78-bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:xtend" /></template>
