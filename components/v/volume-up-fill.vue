<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnhzr4bxv.css';
import '../../css/s/si-8z06fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnhzr4bxv"/><path class="si-8z06fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:volume-up-fill" /></template>
