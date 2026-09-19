<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v09i1dt_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v09i1dt_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sun" /></template>
