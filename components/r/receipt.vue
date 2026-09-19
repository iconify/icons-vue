<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v30otqbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v30otqbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:receipt" /></template>
