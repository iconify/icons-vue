<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq8bs9b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cq8bs9b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scrobblex-light" /></template>
