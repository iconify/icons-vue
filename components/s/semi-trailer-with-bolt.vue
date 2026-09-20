<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld1eu9b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ld1eu9b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:semi-trailer-with-bolt" /></template>
