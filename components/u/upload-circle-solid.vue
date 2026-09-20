<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4r_v4pue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k4r_v4pue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:upload-circle-solid" /></template>
