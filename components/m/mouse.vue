<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epbbbhb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epbbbhb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:mouse" /></template>
