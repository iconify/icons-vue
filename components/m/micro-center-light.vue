<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bks8__b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bks8__b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:micro-center-light" /></template>
