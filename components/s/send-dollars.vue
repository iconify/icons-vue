<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3bbjxk2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3bbjxk2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:send-dollars" /></template>
