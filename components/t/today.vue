<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc7ci5y7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lc7ci5y7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:today" /></template>
