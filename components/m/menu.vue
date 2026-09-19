<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oysi81b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oysi81b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu" /></template>
