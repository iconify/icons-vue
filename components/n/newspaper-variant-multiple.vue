<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be2v6wbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be2v6wbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:newspaper-variant-multiple" /></template>
