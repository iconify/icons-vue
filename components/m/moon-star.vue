<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpm78qb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpm78qb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:moon-star" /></template>
