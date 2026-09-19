<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zop99obdj.css';
import '../../css/d/d0iebyb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zop99obdj"/><path class="d0iebyb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:medkit" /></template>
