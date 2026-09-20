<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2be9pn4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2be9pn4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:oracle-logo-block" /></template>
