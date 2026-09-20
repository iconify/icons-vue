<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeyiptbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeyiptbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-nine-plus-box-multiple-outline" /></template>
