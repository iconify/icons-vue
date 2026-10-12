<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyoqkjb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kyoqkjb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-arrow-right-fill-20" /></template>
