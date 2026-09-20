<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep_htdb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ep_htdb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:share-link" /></template>
