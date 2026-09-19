<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4nlrnb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="s4nlrnb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:u-duo" /></template>
