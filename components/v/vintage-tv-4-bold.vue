<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1pennbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1pennbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:vintage-tv-4-bold" /></template>
