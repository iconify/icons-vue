<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmtmf8b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="kmtmf8b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:podcast" /></template>
