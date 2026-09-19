<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh_rcpr_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1792};
const content = `<path class="mh_rcpr_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:map-pin" /></template>
