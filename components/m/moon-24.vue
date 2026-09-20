<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxse9ubls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxse9ubls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:moon-24" /></template>
