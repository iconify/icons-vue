<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl4umccal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xl4umccal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:right-to-bracket" /></template>
