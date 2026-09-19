<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uswlc2bcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uswlc2bcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:vector" /></template>
