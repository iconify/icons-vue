<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv1jkn-1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tv1jkn-1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:movie" /></template>
