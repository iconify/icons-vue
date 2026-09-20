<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2j2plflq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d2j2plflq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:screen-alt-2-outline" /></template>
