<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_bewjb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_bewjb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thingiverse-light" /></template>
