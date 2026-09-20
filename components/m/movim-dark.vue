<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5-y7okkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g5-y7okkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:movim-dark" /></template>
