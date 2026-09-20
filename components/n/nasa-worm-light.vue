<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_woru4wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_woru4wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasa-worm-light" /></template>
