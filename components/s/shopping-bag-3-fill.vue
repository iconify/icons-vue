<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn1n32bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn1n32bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-bag-3-fill" /></template>
