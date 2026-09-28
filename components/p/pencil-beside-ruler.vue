<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qekq0fbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qekq0fbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pencil-beside-ruler" /></template>
