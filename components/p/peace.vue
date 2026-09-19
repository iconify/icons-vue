<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srl88obkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="srl88obkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:peace" /></template>
