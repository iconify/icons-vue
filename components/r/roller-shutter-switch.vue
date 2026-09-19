<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6w6e1bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6w6e1bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roller-shutter-switch" /></template>
