<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tss2_kbya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tss2_kbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nextbike" /></template>
