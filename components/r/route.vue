<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbzqocshv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="zbzqocshv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:route" /></template>
