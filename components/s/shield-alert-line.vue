<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkzr4h67j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkzr4h67j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-alert-line" /></template>
