<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxg2fn1hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nxg2fn1hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:womens-and-mens-restroom-symbol" /></template>
