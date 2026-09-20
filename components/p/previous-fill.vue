<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4jvy7b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4jvy7b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:previous-fill" /></template>
