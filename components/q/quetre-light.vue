<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p07t8qblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p07t8qblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quetre-light" /></template>
