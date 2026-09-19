<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyx3ri51p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tyx3ri51p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-power" /></template>
