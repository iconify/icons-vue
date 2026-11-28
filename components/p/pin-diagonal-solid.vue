<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqm2czb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqm2czb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pin-diagonal-solid" /></template>
