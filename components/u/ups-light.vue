<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oov0fabhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oov0fabhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ups-light" /></template>
