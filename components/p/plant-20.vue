<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo2_hufaw.css';
import '../../css/k/k4x3-0b4z.css';
import '../../css/f/f2fykithr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wo2_hufaw"/><path class="k4x3-0b4z"/><path class="f2fykithr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plant-20" /></template>
