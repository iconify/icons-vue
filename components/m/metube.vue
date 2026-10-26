<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewj65icda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":500,"height":500};
const content = `<path class="ewj65icda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:metube" /></template>
