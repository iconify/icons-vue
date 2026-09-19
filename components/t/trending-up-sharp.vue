<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0daysu1p.css';
import '../../css/q/qnkrgpaud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0daysu1p"/><path class="qnkrgpaud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:trending-up-sharp" /></template>
