<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc8nh-b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oc8nh-b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:stone-arrowhead-top-right" /></template>
