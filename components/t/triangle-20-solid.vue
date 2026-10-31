<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubssz1bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ubssz1bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:triangle-20-solid" /></template>
