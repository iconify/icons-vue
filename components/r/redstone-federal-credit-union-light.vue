<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5t0um5rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5t0um5rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:redstone-federal-credit-union-light" /></template>
