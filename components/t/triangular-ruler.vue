<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzzpiv8ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dzzpiv8ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:triangular-ruler" /></template>
