<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkn5tq8xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkn5tq8xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:topwithupwardsarrow" /></template>
