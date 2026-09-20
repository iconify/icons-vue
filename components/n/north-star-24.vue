<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbc8lbcof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbc8lbcof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:north-star-24" /></template>
