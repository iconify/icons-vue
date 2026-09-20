<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kydtrpl2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kydtrpl2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:orbs" /></template>
