<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0viuutrh.css';
import '../../css/f/fy-g4rb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0viuutrh"/><path class="fy-g4rb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shield-check-light" /></template>
