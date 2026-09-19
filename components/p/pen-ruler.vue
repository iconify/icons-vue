<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5i22bb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5i22bb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:pen-ruler" /></template>
