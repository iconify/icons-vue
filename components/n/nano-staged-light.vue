<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks918j6of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks918j6of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:nano-staged-light" /></template>
