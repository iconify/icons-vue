<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fngcuz2gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fngcuz2gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:oracle-logo" /></template>
