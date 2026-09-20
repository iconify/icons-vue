<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_fc6-a4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c_fc6-a4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:round-cap-solid" /></template>
