<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8jaicb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x8jaicb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rust-light" /></template>
