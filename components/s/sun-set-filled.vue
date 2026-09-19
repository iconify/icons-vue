<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8m0hfx1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8m0hfx1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-set-filled" /></template>
