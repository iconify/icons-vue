<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_lec65xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_lec65xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:venmo" /></template>
