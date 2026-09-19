<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv0kxeboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jv0kxeboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:pen-to-square" /></template>
