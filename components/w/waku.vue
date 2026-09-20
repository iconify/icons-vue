<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh00q-bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bh00q-bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:waku" /></template>
