<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7-96frbe.css';
import '../../css/x/x-g8qp0ij.css';
import '../../css/i/iw3w-abnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z7-96frbe"/><path class="x-g8qp0ij"/><path class="iw3w-abnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:warning-outline" /></template>
