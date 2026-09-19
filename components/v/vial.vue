<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cseet96gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="cseet96gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:vial" /></template>
