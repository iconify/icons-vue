<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/om7c014xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="om7c014xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-euro" /></template>
