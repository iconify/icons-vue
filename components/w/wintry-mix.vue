<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lga8dlbkm.css';
import '../../css/x/x9stnobdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lga8dlbkm"/><path class="x9stnobdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wintry-mix" /></template>
