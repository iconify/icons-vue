<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co53okb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="co53okb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:teacup-with-steam" /></template>
