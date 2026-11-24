<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3dxg33um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="c3dxg33um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:skip-backward-20-solid" /></template>
