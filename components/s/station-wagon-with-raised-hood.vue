<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2zb1x5to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i2zb1x5to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:station-wagon-with-raised-hood" /></template>
