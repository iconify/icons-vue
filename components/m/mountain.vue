<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu7gmyhby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu7gmyhby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mountain" /></template>
