<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xra_zg-lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xra_zg-lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:visual-studio" /></template>
