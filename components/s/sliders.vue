<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqz9skbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqz9skbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sliders" /></template>
