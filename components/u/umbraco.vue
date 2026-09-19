<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez5cvnbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":510,"height":512};
const content = `<path class="ez5cvnbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:umbraco" /></template>
