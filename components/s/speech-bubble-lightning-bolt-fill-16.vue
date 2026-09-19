<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvvujxbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lvvujxbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-lightning-bolt-fill-16" /></template>
