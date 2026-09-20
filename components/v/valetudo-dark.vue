<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psii9s-rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="psii9s-rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:valetudo-dark" /></template>
