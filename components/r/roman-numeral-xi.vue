<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh-ubxb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lh-ubxb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:roman-numeral-xi" /></template>
