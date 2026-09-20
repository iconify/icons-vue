<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxzmq3bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jxzmq3bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:political" /></template>
