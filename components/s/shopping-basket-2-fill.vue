<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7_2ksbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7_2ksbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shopping-basket-2-fill" /></template>
