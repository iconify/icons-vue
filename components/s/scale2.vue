<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_89b3bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_89b3bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scale2" /></template>
