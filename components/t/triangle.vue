<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vujqufbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vujqufbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:triangle" /></template>
