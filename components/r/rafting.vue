<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq4vz-hqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="mq4vz-hqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:rafting" /></template>
