<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afo943bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="afo943bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:shopping-cart" /></template>
