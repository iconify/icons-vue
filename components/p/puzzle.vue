<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey8tl5bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey8tl5bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:puzzle" /></template>
