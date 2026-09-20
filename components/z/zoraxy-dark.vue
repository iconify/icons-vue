<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwt866bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xwt866bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zoraxy-dark" /></template>
