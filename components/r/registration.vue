<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfmdzgbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lfmdzgbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:registration" /></template>
