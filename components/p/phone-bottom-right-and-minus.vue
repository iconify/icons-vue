<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8-l8jbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t8-l8jbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-bottom-right-and-minus" /></template>
