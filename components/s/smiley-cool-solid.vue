<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5bpuob-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v5bpuob-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-cool-solid" /></template>
