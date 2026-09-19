<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldi8w1b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldi8w1b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:notion" /></template>
