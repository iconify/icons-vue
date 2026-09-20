<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g712a07tq.css';
import '../../css/i/ibxo5zbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="g712a07tq"/><path class="ibxo5zbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:raised-hand-medium-dark-skin-tone" /></template>
