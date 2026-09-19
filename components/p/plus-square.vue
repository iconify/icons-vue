<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8a2skooc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8a2skooc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:plus-square" /></template>
