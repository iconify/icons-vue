<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um4cf3bps.css';
import '../../css/g/g2l6abblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="um4cf3bps"/><path class="g2l6abblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:share-2-48-bold" /></template>
