<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c75k6abxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c75k6abxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:turn-down-right" /></template>
