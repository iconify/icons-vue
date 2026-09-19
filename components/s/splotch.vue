<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi4exwl-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oi4exwl-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:splotch" /></template>
