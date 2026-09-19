<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj8u-yb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj8u-yb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:squares-exclude" /></template>
