<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxiyspb3j.css';
import '../../css/u/ub_apgbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wxiyspb3j"/><path class="ub_apgbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-bold-duotone" /></template>
