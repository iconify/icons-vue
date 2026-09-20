<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_159-btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_159-btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shopware-dark" /></template>
