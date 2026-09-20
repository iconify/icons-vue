<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcc09-bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vcc09-bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tailless-line-arrow-shrink-horizontal-2-remix" /></template>
