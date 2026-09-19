<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd89w8b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd89w8b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:moon-phase-2" /></template>
