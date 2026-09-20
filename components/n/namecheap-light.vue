<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk8e7g4nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tk8e7g4nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:namecheap-light" /></template>
