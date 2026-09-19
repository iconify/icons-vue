<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si_iur2zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si_iur2zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-right-04" /></template>
