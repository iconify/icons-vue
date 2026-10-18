<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jekw5_btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jekw5_btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:volume-2" /></template>
