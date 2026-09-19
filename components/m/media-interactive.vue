<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgwi1hb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dgwi1hb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:media-interactive" /></template>
