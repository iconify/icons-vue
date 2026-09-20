<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr_hbc4nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr_hbc4nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowman-fill" /></template>
