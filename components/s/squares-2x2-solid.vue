<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzqs9yb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzqs9yb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:squares-2x2-solid" /></template>
