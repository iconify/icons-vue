<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlpxkebuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mlpxkebuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nightscout-light" /></template>
