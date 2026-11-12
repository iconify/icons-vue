<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhgko-bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jhgko-bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinepods-dark" /></template>
