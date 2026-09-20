<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j086mhb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j086mhb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tiddlywiki-light" /></template>
