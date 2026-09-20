<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2blipbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t2blipbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metatana-light" /></template>
