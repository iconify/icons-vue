<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyc56ubjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oyc56ubjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:page-break-solid" /></template>
