<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5g7s0cqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5g7s0cqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sound-light" /></template>
