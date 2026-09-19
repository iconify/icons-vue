<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfggz2bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfggz2bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:square-full" /></template>
