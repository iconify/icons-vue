<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcr02fcny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mcr02fcny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:open-umbrella" /></template>
