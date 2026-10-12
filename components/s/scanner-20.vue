<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2wv7tbdk.css';
import '../../css/f/flbhffbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y2wv7tbdk"/><path class="flbhffbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scanner-20" /></template>
