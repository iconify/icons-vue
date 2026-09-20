<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl0xf91ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pl0xf91ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subtrackr-light" /></template>
