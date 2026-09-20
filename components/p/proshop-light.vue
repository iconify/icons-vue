<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mino6h8rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mino6h8rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:proshop-light" /></template>
