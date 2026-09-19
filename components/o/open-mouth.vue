<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2sf9e_hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2sf9e_hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:open-mouth" /></template>
