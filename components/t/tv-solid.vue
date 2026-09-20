<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddyyrvbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ddyyrvbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:tv-solid" /></template>
