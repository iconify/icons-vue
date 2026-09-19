<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfu-amb1j.css';
import '../../css/l/lrbukw_4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfu-amb1j"/><path class="lrbukw_4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trophy-star" /></template>
