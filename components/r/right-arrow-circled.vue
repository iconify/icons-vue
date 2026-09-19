<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxv29_lqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kxv29_lqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-arrow-circled" /></template>
