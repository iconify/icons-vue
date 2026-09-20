<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km-1_cczy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="km-1_cczy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-map-pin-with-dot" /></template>
