<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be98cq8ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="be98cq8ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:nightstand4" /></template>
