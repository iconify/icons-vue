<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpvwby7ij.css';
import '../../css/n/nqmg7ebpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpvwby7ij"/><path class="nqmg7ebpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:water-meter" /></template>
