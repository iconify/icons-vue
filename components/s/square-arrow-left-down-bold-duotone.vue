<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/madko4bbz.css';
import '../../css/f/fgkwccyip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="madko4bbz"/><path class="fgkwccyip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-arrow-left-down-bold-duotone" /></template>
