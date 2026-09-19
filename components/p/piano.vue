<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhk06ihte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="lhk06ihte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:piano" /></template>
