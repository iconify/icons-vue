<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6er-z6mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6er-z6mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stoat-light" /></template>
