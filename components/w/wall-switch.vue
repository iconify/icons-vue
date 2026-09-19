<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luy794bvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luy794bvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-switch" /></template>
