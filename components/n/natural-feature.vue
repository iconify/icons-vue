<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luts3yb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="luts3yb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:natural-feature" /></template>
