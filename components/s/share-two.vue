<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upzee6b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="upzee6b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:share-two" /></template>
