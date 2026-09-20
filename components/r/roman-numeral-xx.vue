<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifk465b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ifk465b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-xx" /></template>
