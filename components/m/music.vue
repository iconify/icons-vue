<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuqbkbcqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuqbkbcqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:music" /></template>
