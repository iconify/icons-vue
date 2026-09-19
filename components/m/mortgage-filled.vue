<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f69w6uxsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f69w6uxsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:mortgage-filled" /></template>
