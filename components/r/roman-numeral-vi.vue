<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz-i4060t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hz-i4060t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-vi" /></template>
