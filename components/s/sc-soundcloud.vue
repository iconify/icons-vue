<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0s0by2sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="o0s0by2sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-soundcloud" /></template>
