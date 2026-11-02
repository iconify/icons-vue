<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cww1_ybzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cww1_ybzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-sleeping-in-bunkbeds-in-eaved-gabled-building-with-chimney" /></template>
