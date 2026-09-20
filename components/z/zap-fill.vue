<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iiy75sbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iiy75sbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:zap-fill" /></template>
