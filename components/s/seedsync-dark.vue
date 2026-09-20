<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf7n-7b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xf7n-7b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seedsync-dark" /></template>
