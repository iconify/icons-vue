<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l51-jigzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l51-jigzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:menu-cake" /></template>
