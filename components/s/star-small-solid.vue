<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmr3fxbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dmr3fxbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:star-small-solid" /></template>
