<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1zc5nbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g1zc5nbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oneuptime-dark" /></template>
