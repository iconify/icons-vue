<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5t102bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y5t102bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pent-no-light" /></template>
