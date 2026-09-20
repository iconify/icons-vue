<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri6lrnb_l.css';
import '../../css/i/ibxo5zbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ri6lrnb_l"/><path class="ibxo5zbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:raised-hand-light-skin-tone" /></template>
