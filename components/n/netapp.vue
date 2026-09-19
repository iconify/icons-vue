<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c67s0abyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c67s0abyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:netapp" /></template>
