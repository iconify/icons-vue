<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvpkry_-f.css';
import '../../css/m/m3d6pw-jx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":55.4,"height":48};
const content = `<path class="kvpkry_-f"/><path class="m3d6pw-jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:workos-dark" /></template>
