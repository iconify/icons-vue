<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt5c8ebqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt5c8ebqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:x" /></template>
