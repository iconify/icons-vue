<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlom2gbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlom2gbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:olympic-rings" /></template>
