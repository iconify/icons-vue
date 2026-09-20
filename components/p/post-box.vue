<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv-6pcczn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="dv-6pcczn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:post-box" /></template>
