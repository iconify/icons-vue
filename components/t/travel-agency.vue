<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqd4un0bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jqd4un0bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:travel-agency" /></template>
