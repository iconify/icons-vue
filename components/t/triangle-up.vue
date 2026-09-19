<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4ch4hsgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ch4hsgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:triangle-up" /></template>
