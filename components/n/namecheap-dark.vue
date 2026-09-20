<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swmlmj4nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swmlmj4nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:namecheap-dark" /></template>
