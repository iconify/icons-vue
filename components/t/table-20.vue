<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wetq5b_1u.css';
import '../../css/d/d1j6p8b_k.css';
import '../../css/q/qqk1d6grf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wetq5b_1u"/><path class="d1j6p8b_k"/><path class="qqk1d6grf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:table-20" /></template>
