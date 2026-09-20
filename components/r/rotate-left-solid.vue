<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzoul-_gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uzoul-_gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:rotate-left-solid" /></template>
