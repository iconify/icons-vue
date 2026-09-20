<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qifv46pei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="qifv46pei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:route-pin" /></template>
