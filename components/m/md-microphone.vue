<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oywppeflk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oywppeflk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-microphone" /></template>
