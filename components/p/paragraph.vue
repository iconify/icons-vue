<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc34h_bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="jc34h_bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:paragraph" /></template>
