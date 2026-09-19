<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4h35nmyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="z4h35nmyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-telegram" /></template>
