<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkz-23bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pkz-23bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wrench" /></template>
