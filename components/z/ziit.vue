<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgysx_b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zgysx_b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ziit" /></template>
