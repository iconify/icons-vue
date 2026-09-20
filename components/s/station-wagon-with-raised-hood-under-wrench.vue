<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7am3obid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l7am3obid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:station-wagon-with-raised-hood-under-wrench" /></template>
