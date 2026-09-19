<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sadjwebhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="sadjwebhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:street-light-outline" /></template>
