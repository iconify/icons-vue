<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igqmfsbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2656,"height":2080};
const content = `<path class="igqmfsbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:male-female" /></template>
