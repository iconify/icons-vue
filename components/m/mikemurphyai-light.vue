<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epal7ia0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="epal7ia0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mikemurphyai-light" /></template>
