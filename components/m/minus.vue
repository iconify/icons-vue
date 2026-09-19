<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4kpq-8ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4kpq-8ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:minus" /></template>
