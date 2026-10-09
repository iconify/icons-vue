<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2v7xkiqi.css';
import '../../css/e/egxp91bbt.css';
import '../../css/a/agzo0q31v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t2v7xkiqi"/><path class="egxp91bbt"/><path class="agzo0q31v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-meter-20-bold" /></template>
