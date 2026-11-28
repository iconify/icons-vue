<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-gjakbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-gjakbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tablet-x" /></template>
