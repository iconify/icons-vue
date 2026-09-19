<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpqh3i39z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kpqh3i39z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:phone-telephone" /></template>
