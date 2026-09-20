<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veh--ghsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="veh--ghsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pixiv-light" /></template>
