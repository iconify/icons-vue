<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npn5p1brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":963,"height":1000};
const content = `<path class="npn5p1brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:signal" /></template>
