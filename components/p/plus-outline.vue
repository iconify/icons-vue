<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp6kl1uty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wp6kl1uty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:plus-outline" /></template>
