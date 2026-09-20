<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7_ank21w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7_ank21w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:powers" /></template>
