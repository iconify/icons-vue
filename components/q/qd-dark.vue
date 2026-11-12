<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krnj30b0h.css';
import '../../css/n/n8uyb4pln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="krnj30b0h"/><path class="n8uyb4pln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qd-dark" /></template>
