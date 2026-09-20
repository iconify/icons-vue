<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bla-e4b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bla-e4b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xxl-sports" /></template>
