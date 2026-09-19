<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqbvt3vys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dqbvt3vys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:save-outline" /></template>
