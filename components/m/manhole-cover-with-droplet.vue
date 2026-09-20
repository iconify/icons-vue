<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvzi4p1_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wvzi4p1_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:manhole-cover-with-droplet" /></template>
