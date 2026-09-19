<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbb35bbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="wbb35bbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:target-two" /></template>
