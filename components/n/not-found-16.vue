<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcb8zfcla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gcb8zfcla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:not-found-16" /></template>
