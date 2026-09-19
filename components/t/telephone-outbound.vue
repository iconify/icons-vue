<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-ux0x7wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d-ux0x7wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:telephone-outbound" /></template>
