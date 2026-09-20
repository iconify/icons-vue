<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot9-f-jds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ot9-f-jds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:south-dakota" /></template>
