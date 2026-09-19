<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k162hpbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k162hpbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mars" /></template>
