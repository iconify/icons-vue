<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_9832jzs.css';
import '../../css/s/s5cgq7bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="d_9832jzs"/><path class="s5cgq7bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:watch-outline" /></template>
