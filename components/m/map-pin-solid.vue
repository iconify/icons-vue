<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjgcx4_5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wjgcx4_5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:map-pin-solid" /></template>
