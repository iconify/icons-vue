<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o14m0cc9r.css';
import '../../css/z/z7gbrqbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="o14m0cc9r"/><path class="z7gbrqbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:pricetag-multiple" /></template>
