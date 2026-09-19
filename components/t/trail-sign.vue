<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldz9pm7fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ldz9pm7fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:trail-sign" /></template>
