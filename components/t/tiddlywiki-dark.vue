<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pga6wlxad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pga6wlxad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tiddlywiki-dark" /></template>
