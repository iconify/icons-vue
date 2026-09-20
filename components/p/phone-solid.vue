<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxacudx8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pxacudx8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:phone-solid" /></template>
