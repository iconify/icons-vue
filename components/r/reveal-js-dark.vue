<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an7_bbc4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="an7_bbc4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reveal-js-dark" /></template>
