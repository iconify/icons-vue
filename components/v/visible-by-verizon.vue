<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s42bbq7uz.css';
import '../../css/d/do2_d_k7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s42bbq7uz"/><path class="do2_d_k7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visible-by-verizon" /></template>
