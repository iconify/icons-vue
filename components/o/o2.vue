<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsvjai1rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsvjai1rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:o2" /></template>
