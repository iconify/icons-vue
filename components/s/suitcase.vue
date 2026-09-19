<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcsms5bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bcsms5bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:suitcase" /></template>
