<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7w644ytb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7w644ytb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:thin-long-right" /></template>
