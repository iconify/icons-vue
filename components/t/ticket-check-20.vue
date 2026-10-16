<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl41xxbat.css';
import '../../css/j/jeuojelkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tl41xxbat"/><path class="jeuojelkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ticket-check-20" /></template>
