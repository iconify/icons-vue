<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n32go5b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="n32go5b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:square-minus" /></template>
