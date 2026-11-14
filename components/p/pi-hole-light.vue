<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk44qabdq.css';
import '../../css/j/jpd9n3d1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xk44qabdq"/><path class="jpd9n3d1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-hole-light" /></template>
