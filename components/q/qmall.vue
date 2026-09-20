<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psh1nub4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psh1nub4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:qmall" /></template>
