<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fctqu-jjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fctqu-jjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:test-tube-fill" /></template>
