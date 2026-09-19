<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh1s9nbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh1s9nbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:refrigerator" /></template>
